<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz5nuxbgv.css';
import '../../css/s/szs1rbc2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nz5nuxbgv"/><path class="szs1rbc2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lemmy" {...props}></Icon>
