<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ze41jub0z.css';
import '../../css/q/qr98xybve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ze41jub0z"/><path class="qr98xybve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:microscope-filled" {...props}></Icon>
