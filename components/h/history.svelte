<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqd8dx1br.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yqd8dx1br"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:history" {...props}></Icon>
