<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/oj79fp0oa.css';
import '../../css/f/fr4pg2b_d.css';
import '../../css/o/ojke_mb9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="oj79fp0oa"/><path class="fr4pg2b_d"/><path class="ojke_mb9w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:necklace" {...props}></Icon>
