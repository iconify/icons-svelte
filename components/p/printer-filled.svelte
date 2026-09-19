<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8owdqtsa.css';
import '../../css/w/wrt-x_0am.css';
import '../../css/d/dt3g_4q-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d8owdqtsa"/><circle class="wrt-x_0am"/><path class="dt3g_4q-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:printer-filled" {...props}></Icon>
