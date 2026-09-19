<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sh8f0lv2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sh8f0lv2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:assembly-sparc" {...props}></Icon>
