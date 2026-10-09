<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-7yzwbmb.css';
import '../../css/n/n0tshoxcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="a-7yzwbmb"/><path class="n0tshoxcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fast-forward-20" {...props}></Icon>
