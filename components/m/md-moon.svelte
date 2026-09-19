<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3v9z9dcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w3v9z9dcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-moon" {...props}></Icon>
