<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxrxnizhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wxrxnizhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:backward" {...props}></Icon>
