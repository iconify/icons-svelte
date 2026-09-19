<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/sks-tacsx.css';
import '../../css/h/hsmtyjbkf.css';
import '../../css/l/ld5saecis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="sks-tacsx"/><path class="hsmtyjbkf"/><path class="ld5saecis"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:bell-minus" {...props}></Icon>
