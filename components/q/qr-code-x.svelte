<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qkrka85cr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qkrka85cr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:qr-code-x" {...props}></Icon>
