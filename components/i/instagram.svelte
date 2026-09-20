<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/ak_npccsm.css';
import '../../css/n/n14m7qbat.css';
import '../../css/s/sb5o2gexg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><rect class="ak_npccsm"/><circle class="n14m7qbat"/><circle class="sb5o2gexg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:instagram" {...props}></Icon>
