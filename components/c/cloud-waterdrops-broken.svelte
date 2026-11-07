<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/c/cz_ntqbfa.css';
import '../../css/r/rxf5pixtu.css';
import '../../css/e/e6k5rfbvz.css';
import '../../css/n/nc6t2vbek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="cz_ntqbfa"/><path class="rxf5pixtu"/><path class="e6k5rfbvz"/><path class="nc6t2vbek"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cloud-waterdrops-broken" {...props}></Icon>
