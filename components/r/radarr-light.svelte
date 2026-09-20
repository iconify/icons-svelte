<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lyfq0hydv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lyfq0hydv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:radarr-light" {...props}></Icon>
