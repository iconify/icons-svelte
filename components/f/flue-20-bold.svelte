<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xlpz3ljgc.css';
import '../../css/x/xp0bkxb5p.css';
import '../../css/b/bwm_8acuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xlpz3ljgc"/><path class="xp0bkxb5p"/><path class="bwm_8acuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:flue-20-bold" {...props}></Icon>
