<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/m/mp2i09jnb.css';
import '../../css/y/yovjd0b3i.css';
import '../../css/l/l3k3plb5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="mp2i09jnb"/><path class="yovjd0b3i"/><path class="l3k3plb5z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:browser-key" {...props}></Icon>
