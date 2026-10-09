<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewxalfyww.css';
import '../../css/j/jxwwvvbjb.css';
import '../../css/t/tp0bwlbkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ewxalfyww"/><path class="jxwwvvbjb"/><path class="tp0bwlbkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heat-exchanger-20-bold" {...props}></Icon>
