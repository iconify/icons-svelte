<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p67p4-ffp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p67p4-ffp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:netalertx-dark" {...props}></Icon>
