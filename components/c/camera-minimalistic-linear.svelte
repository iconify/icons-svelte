<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/fr_tmn9fp.css';
import '../../css/j/jot55yhti.css';
import '../../css/x/x4pob2bni.css';
import '../../css/b/bcpsrtbhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="fr_tmn9fp"/><path class="jot55yhti"/><path class="x4pob2bni"/><path class="bcpsrtbhb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:camera-minimalistic-linear" {...props}></Icon>
