<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dz5_qkdfv.css';
import '../../css/m/mu_rg1b1t.css';
import '../../css/w/wpp7bqbdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dz5_qkdfv"/><path class="mu_rg1b1t"/><path class="wpp7bqbdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hot-water-20" {...props}></Icon>
