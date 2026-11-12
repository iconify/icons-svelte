<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-zw2h7ds.css';
import '../../css/a/acmcm-bzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z-zw2h7ds"/><path class="acmcm-bzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-tag-manager-dark" {...props}></Icon>
