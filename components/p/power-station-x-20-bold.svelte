<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4slh4bwa.css';
import '../../css/t/td-ybovkx.css';
import '../../css/f/fnaxk-b_r.css';
import '../../css/j/jzeh2cbeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w4slh4bwa"/><path class="td-ybovkx"/><path class="fnaxk-b_r"/><path class="jzeh2cbeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:power-station-x-20-bold" {...props}></Icon>
