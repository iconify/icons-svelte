<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/civmh-b8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="civmh-b8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:newspaper" {...props}></Icon>
