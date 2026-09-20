<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ix5kfyb-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ix5kfyb-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bolt-diy-light" {...props}></Icon>
