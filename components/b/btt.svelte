<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqm3efwxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wqm3efwxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:btt" {...props}></Icon>
