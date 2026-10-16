<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6_s1zkbf.css';
import '../../css/t/th83uglwj.css';
import '../../css/t/t2zfzobxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="e6_s1zkbf"/><path class="th83uglwj"/><path class="t2zfzobxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hazard-biohazard-20" {...props}></Icon>
