<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lx1s_bbyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lx1s_bbyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:paperclip-minus" {...props}></Icon>
