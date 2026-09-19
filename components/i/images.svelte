<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmc6bf_jc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="tmc6bf_jc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:images" {...props}></Icon>
