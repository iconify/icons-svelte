<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/mrobosv7g.css';
import '../../css/v/v-y89qb7a.css';
import '../../css/i/ij7wzu9ga.css';
import '../../css/o/ohlnn7bxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="mrobosv7g"/><path class="v-y89qb7a"/><path class="ij7wzu9ga"/><path class="ohlnn7bxo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:move-broken" {...props}></Icon>
