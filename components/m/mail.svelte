<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2wot4b3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":448};
const content = `<path class="p2wot4b3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:mail" {...props}></Icon>
