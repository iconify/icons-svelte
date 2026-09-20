<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrlf1oakz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yrlf1oakz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:infinity" {...props}></Icon>
