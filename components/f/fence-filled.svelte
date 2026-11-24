<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnp_xxbvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pnp_xxbvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:fence-filled" {...props}></Icon>
