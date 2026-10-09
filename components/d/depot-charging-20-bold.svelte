<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qiuahbcqc.css';
import '../../css/n/nri5-qgzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qiuahbcqc"/><path class="nri5-qgzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:depot-charging-20-bold" {...props}></Icon>
