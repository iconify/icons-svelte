<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ysth-06qa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ysth-06qa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ovh" {...props}></Icon>
