<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ad5--ibbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ad5--ibbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:girl-open-mouth" {...props}></Icon>
