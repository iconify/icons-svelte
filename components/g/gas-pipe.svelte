<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/s/seuormdxt.css';
import '../../css/b/br8th3blo.css';
import '../../css/b/buhh-db0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="seuormdxt"/><path class="br8th3blo"/><path class="buhh-db0h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:gas-pipe" {...props}></Icon>
