<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmz_-_bep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fmz_-_bep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:qr-code-01" {...props}></Icon>
