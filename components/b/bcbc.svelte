<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ad6uctxxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ad6uctxxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:bcbc" {...props}></Icon>
