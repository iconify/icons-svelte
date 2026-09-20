<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/s19aowben.css';
import '../../css/f/fub8u0bsr.css';
import '../../css/q/q9lv46bbv.css';
import '../../css/u/utbx9q75k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="s19aowben"/><path class="fub8u0bsr"/><path class="q9lv46bbv"/><path class="utbx9q75k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:list-up-minimalistic-line-duotone" {...props}></Icon>
