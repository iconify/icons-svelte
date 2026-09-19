<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/knpt5p59u.css';
import '../../css/o/oe7093-zs.css';
import '../../css/y/y9pit_b0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="knpt5p59u"/><path class="oe7093-zs"/><path class="y9pit_b0w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:gameboy" {...props}></Icon>
