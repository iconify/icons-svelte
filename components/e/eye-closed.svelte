<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8se3bqps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="y8se3bqps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:eye-closed" {...props}></Icon>
