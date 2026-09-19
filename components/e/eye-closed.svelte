<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/b/b4gzso3dl.css';
import '../../css/z/z3v-smg0b.css';
import '../../css/b/bc_7zo_yk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="b4gzso3dl"/><path class="z3v-smg0b"/><path class="bc_7zo_yk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:eye-closed" {...props}></Icon>
