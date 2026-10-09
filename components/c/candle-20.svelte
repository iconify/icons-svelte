<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/io9vencun.css';
import '../../css/z/z9lj_eqfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="io9vencun"/><path class="z9lj_eqfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:candle-20" {...props}></Icon>
