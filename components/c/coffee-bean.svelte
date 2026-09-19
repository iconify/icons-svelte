<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ie6mjcplv.css';
import '../../css/v/v_suxqb2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ie6mjcplv"/><path class="v_suxqb2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:coffee-bean" {...props}></Icon>
