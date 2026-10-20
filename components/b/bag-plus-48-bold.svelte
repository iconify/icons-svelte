<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqivvfbyi.css';
import '../../css/m/m6q9glbvh.css';
import '../../css/k/k598mbbge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="aqivvfbyi"/><path class="m6q9glbvh"/><path class="k598mbbge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bag-plus-48-bold" {...props}></Icon>
