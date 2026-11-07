<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxvd-g65l.css';
import '../../css/s/srdp-xb5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rxvd-g65l"/><path clip-rule="evenodd" class="srdp-xb5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cloud-bolt-minimalistic-bold-duotone" {...props}></Icon>
