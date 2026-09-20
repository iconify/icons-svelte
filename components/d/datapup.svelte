<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txtpdbbzb.css';
import '../../css/t/t2cfwekii.css';
import '../../css/z/zvi_0b-ar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="txtpdbbzb"/><path class="t2cfwekii"/><path class="zvi_0b-ar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:datapup" {...props}></Icon>
