<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tm4sl1b2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="tm4sl1b2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:preset-ab" {...props}></Icon>
