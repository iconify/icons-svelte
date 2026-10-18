<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckmbmabfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ckmbmabfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:qr-code" {...props}></Icon>
