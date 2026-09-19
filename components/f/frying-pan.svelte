<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ma2b51-lq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ma2b51-lq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:frying-pan" {...props}></Icon>
