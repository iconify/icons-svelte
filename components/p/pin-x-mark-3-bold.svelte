<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4x9v31po.css';
import '../../css/g/g8g82bb_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i4x9v31po"/><path class="g8g82bb_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:pin-x-mark-3-bold" {...props}></Icon>
