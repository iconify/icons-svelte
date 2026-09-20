<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4dzfdcda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n4dzfdcda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:download" {...props}></Icon>
