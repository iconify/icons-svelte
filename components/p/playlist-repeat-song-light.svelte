<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/g/g-vmp1bpt.css';
import '../../css/t/tdirdccsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="g-vmp1bpt"/><path class="tdirdccsl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:playlist-repeat-song-light" {...props}></Icon>
