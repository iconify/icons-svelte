<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1v_-3v3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m1v_-3v3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chevrons-down" {...props}></Icon>
