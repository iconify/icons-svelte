<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/n/ndq0ugbyy.css';
import '../../css/q/qu0eyjbrg.css';
import '../../css/m/m390b8qby.css';
import '../../css/r/ruv56nblh.css';
import '../../css/r/r_va8z9vn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ndq0ugbyy"/><path class="qu0eyjbrg"/><path class="m390b8qby"/><path class="ruv56nblh"/><path class="r_va8z9vn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:clipboard-broken" {...props}></Icon>
