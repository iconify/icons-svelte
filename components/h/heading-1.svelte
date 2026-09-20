<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ra9ry8b0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ra9ry8b0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:heading-1" {...props}></Icon>
