<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zb4jfgbek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zb4jfgbek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:printer" {...props}></Icon>
