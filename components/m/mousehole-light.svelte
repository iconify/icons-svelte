<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zh-l097mh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zh-l097mh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mousehole-light" {...props}></Icon>
