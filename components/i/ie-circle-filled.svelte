<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdcff_hzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wdcff_hzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:ie-circle-filled" {...props}></Icon>
