<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/stm_q-k-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="stm_q-k-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-gas-pump" {...props}></Icon>
