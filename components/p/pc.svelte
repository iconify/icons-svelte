<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fn9-vhbwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":328,"height":512};
const content = `<path class="fn9-vhbwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:pc" {...props}></Icon>
