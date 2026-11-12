<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/no3pe0d-x.css';
import '../../css/c/c03hhtb_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="no3pe0d-x"/><path class="c03hhtb_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-translate-dark" {...props}></Icon>
