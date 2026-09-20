<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtse33bam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xtse33bam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:listmonk" {...props}></Icon>
