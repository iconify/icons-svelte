<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acm-y3bpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="acm-y3bpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:list-check-minimalistic-outline" {...props}></Icon>
