<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmi_zrsne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pmi_zrsne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:plikshare-light" {...props}></Icon>
