<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ic8rdibgp.css';
import '../../css/x/xrb5f7bdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="ic8rdibgp"/><path class="xrb5f7bdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ecowitt" {...props}></Icon>
