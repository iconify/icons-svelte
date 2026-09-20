<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n96zpkbsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n96zpkbsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:opensearch-light" {...props}></Icon>
