<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2m6tab3g.css';
import '../../css/v/v799lmbxv.css';
import '../../css/v/vnf_fxb6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f2m6tab3g"/><path class="v799lmbxv"/><path class="vnf_fxb6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:food-drink-tea" {...props}></Icon>
