<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zw98ts_6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="zw98ts_6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:connectdevelop" {...props}></Icon>
