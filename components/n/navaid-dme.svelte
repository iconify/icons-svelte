<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-u4xnbot.css';
import '../../css/o/oa5_b0b8m.css';
import '../../css/z/zq-0s9biw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m-u4xnbot"/><path class="oa5_b0b8m"/><path class="zq-0s9biw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:navaid-dme" {...props}></Icon>
