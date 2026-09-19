<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvq7ecbic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="dvq7ecbic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:holder-outlined" {...props}></Icon>
