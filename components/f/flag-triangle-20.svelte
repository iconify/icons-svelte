<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ks0oxbcgz.css';
import '../../css/x/xzejhphye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ks0oxbcgz"/><path class="xzejhphye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:flag-triangle-20" {...props}></Icon>
