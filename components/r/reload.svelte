<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/r/rdnexrb-i.css';
import '../../css/t/tbnh3xbqt.css';
import '../../css/b/bq_htov1v.css';
import '../../css/p/p5eo-acjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="rdnexrb-i"/><path class="tbnh3xbqt"/><path class="bq_htov1v"/><path class="p5eo-acjt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:reload" {...props}></Icon>
