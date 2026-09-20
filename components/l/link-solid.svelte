<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yowhw89bu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yowhw89bu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:link-solid" {...props}></Icon>
