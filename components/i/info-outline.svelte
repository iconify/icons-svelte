<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wckr9kb1z.css';
import '../../css/w/wq8x2ubgv.css';
import '../../css/i/i1u8a2d8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wckr9kb1z"/><circle class="wq8x2ubgv"/><path class="i1u8a2d8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:info-outline" {...props}></Icon>
