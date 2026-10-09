<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewbuvvbog.css';
import '../../css/z/zh3_rg95y.css';
import '../../css/j/j7vic2sbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ewbuvvbog"/><path class="zh3_rg95y"/><path class="j7vic2sbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mail-check-20" {...props}></Icon>
