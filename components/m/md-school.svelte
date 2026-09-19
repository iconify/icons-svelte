<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtyhg7ndl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rtyhg7ndl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-school" {...props}></Icon>
