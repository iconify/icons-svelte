<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3jx_2bdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l3jx_2bdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mail-archiver-light" {...props}></Icon>
