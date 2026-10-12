<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0eeh3bce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g0eeh3bce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:qr-code-filled" {...props}></Icon>
