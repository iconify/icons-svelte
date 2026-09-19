<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1suj6g3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":384};
const content = `<path class="v1suj6g3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:long-arrow-down" {...props}></Icon>
