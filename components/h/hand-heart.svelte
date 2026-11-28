<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6r9xybbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s6r9xybbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:hand-heart" {...props}></Icon>
