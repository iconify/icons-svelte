<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r__2x3s5d.css';
import '../../css/c/cjbp44b0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="r__2x3s5d"/><path class="cjbp44b0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:charger-fast-20-bold" {...props}></Icon>
