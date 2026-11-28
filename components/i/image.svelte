<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccb16yb8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ccb16yb8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:image" {...props}></Icon>
