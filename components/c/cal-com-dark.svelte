<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxp5dgbxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wxp5dgbxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cal-com-dark" {...props}></Icon>
