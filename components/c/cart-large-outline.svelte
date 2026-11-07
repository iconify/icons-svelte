<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfjrhsbdn.css';
import '../../css/t/tvzowjb2p.css';
import '../../css/m/mym-u-jww.css';
import '../../css/b/bogwy2v0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gfjrhsbdn"/><path clip-rule="evenodd" class="tvzowjb2p"/><path clip-rule="evenodd" class="mym-u-jww"/><path clip-rule="evenodd" class="bogwy2v0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cart-large-outline" {...props}></Icon>
