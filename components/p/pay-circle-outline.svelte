<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sz77wfhmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="sz77wfhmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:pay-circle-outline" {...props}></Icon>
