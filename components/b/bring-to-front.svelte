<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywxq2xbbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ywxq2xbbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:bring-to-front" {...props}></Icon>
