<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eheil_bpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eheil_bpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:lemon-squeezy-fill" {...props}></Icon>
