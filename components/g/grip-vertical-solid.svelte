<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgjelwbnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xgjelwbnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:grip-vertical-solid" {...props}></Icon>
