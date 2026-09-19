<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/o8gm9zlaa.css';
import '../../css/i/iss23tpjy.css';
import '../../css/k/ki55z6ilg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="o8gm9zlaa"/><path class="iss23tpjy"/><path class="ki55z6ilg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:briefcase-business" {...props}></Icon>
