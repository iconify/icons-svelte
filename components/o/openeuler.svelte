<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmeey5brg.css';
import '../../css/q/q194_cbxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lmeey5brg"/><path class="q194_cbxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openeuler" {...props}></Icon>
