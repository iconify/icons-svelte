<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/m_uf8kb5f.css';
import '../../css/z/z49mobc8s.css';
import '../../css/n/nqop7gbey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="m_uf8kb5f"/><path class="z49mobc8s"/><path class="nqop7gbey"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chevron-last-broken" {...props}></Icon>
