<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oamm76ujh.css';
import '../../css/i/i72iigb4y.css';
import '../../css/z/zfyv2h51a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oamm76ujh"/><path class="i72iigb4y"/><path class="zfyv2h51a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-tux" {...props}></Icon>
