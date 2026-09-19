<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/a/aw2wtqber.css';
import '../../css/v/v7e71vdzm.css';
import '../../css/f/fx_6-bche.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="aw2wtqber"/><path class="v7e71vdzm"/><path class="fx_6-bche"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cpu-settings" {...props}></Icon>
