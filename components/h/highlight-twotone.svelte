<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3i704izb.css';
import '../../css/r/rypnjzb0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="l3i704izb"/><path class="rypnjzb0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:highlight-twotone" {...props}></Icon>
