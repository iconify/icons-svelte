<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xc6_jgsyo.css';
import '../../css/t/tc5lk5bgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xc6_jgsyo"/><path class="tc5lk5bgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:bed-single-solid" {...props}></Icon>
