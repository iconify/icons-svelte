<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncg4ydbbh.css';
import '../../css/r/r2vjdgbir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ncg4ydbbh"/><path class="r2vjdgbir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-django" {...props}></Icon>
