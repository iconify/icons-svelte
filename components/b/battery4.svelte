<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ceecv5bzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ceecv5bzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:battery4" {...props}></Icon>
