<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8kpddbfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w8kpddbfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-pint" {...props}></Icon>
