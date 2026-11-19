<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n65kb88kt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n65kb88kt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:artcraft-dark" {...props}></Icon>
