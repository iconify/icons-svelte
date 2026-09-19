<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4pxzd2th.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n4pxzd2th"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:dgd" {...props}></Icon>
