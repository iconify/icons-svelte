<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l0uk8wbky.css';
import '../../css/a/acmcm-bzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l0uk8wbky"/><path class="acmcm-bzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-tag-manager-dark" {...props}></Icon>
