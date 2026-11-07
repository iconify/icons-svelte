<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/fyr67fbfm.css';
import '../../css/e/e_wor2bbs.css';
import '../../css/l/lm7otu1mj.css';
import '../../css/b/bu-wc30dp.css';
import '../../css/g/gvinp5b1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="fyr67fbfm"/><path class="e_wor2bbs"/><path class="lm7otu1mj"/><path class="bu-wc30dp"/><path class="gvinp5b1p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:flash-drive-broken" {...props}></Icon>
