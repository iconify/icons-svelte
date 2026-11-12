<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvu2p6bej.css';
import '../../css/v/v_h7thdam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dvu2p6bej"/><path class="v_h7thdam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:perfice-light" {...props}></Icon>
