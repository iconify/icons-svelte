<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcowhso_o.css';
import '../../css/v/vnjuuubcl.css';
import '../../css/o/oxuzwkbyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zcowhso_o"/><path class="vnjuuubcl"/><path class="oxuzwkbyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ringlink" {...props}></Icon>
