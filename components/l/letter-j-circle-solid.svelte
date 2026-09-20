<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjek9bckt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rjek9bckt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-j-circle-solid" {...props}></Icon>
