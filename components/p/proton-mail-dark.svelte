<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p39_dg31u.css';
import '../../css/l/lj93ifb1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p39_dg31u"/><path class="lj93ifb1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:proton-mail-dark" {...props}></Icon>
