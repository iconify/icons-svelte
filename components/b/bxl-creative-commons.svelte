<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzpap0btc.css';
import '../../css/y/ydu5kibqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gzpap0btc"/><path class="ydu5kibqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-creative-commons" {...props}></Icon>
