<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpwuex3wr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dpwuex3wr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-word-2000-light" {...props}></Icon>
