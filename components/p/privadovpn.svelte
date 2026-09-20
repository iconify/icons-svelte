<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjwqrtb-a.css';
import '../../css/e/e4du2zpbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xjwqrtb-a"/><path class="e4du2zpbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:privadovpn" {...props}></Icon>
