<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sehd02_tk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sehd02_tk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:humble-bundle" {...props}></Icon>
