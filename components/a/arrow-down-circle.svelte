<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/g/gga51ivtj.css';
import '../../css/a/axbjplbgg.css';
import '../../css/n/n5pc76bja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="gga51ivtj"/><path class="axbjplbgg"/><path class="n5pc76bja"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:arrow-down-circle" {...props}></Icon>
