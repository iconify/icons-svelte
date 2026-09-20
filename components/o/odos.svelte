<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezvi_qpnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ezvi_qpnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:odos" {...props}></Icon>
