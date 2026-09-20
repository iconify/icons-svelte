<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9b65p45j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w9b65p45j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:play" {...props}></Icon>
