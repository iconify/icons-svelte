<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxri9acom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dxri9acom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:cloudflare" {...props}></Icon>
