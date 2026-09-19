<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/l/lpbpumbgd.css';
import '../../css/f/flp6ugnrw.css';
import '../../css/a/ajk_qvbds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><circle class="lpbpumbgd"/><circle class="flp6ugnrw"/><path class="ajk_qvbds"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:locate-fixed" {...props}></Icon>
