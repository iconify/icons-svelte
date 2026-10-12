<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpfoayb6f.css';
import '../../css/z/zp19y9ojo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fpfoayb6f"/><path class="zp19y9ojo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:bell-electric-filled" {...props}></Icon>
