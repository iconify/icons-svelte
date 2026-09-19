<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/i/i6bc1bbpn.css';
import '../../css/s/sg--oqwwb.css';
import '../../css/a/afgrcjb4w.css';
import '../../css/k/k0l0khh9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="i6bc1bbpn"/><path class="sg--oqwwb"/><path class="afgrcjb4w"/><path class="k0l0khh9s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:database-locked" {...props}></Icon>
