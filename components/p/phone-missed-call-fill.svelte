<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_hs9s_lv.css';
import '../../css/n/nikou0bxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d_hs9s_lv"/><path class="nikou0bxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:phone-missed-call-fill" {...props}></Icon>
