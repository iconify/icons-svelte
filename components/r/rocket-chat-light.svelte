<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hjdl1fw-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hjdl1fw-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rocket-chat-light" {...props}></Icon>
