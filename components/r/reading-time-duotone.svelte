<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnnw44bzb.css';
import '../../css/q/q810p6bpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vnnw44bzb"/><path class="q810p6bpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:reading-time-duotone" {...props}></Icon>
