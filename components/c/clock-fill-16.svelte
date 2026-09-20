<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3ne6lb_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="t3ne6lb_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:clock-fill-16" {...props}></Icon>
