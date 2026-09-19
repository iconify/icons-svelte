<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yp2ktcbbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yp2ktcbbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:philpapers" {...props}></Icon>
