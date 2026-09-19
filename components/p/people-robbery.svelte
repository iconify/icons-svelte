<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yoti3ubhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="yoti3ubhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:people-robbery" {...props}></Icon>
