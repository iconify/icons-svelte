<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjykl1blt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cjykl1blt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:color-picker-empty" {...props}></Icon>
