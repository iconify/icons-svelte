<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7kdrlpcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t7kdrlpcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:pin-off" {...props}></Icon>
