<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/u/u04hmj8af.css';
import '../../css/i/iv0wkhbcp.css';
import '../../css/m/mw42pob4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="u04hmj8af"/><path class="iv0wkhbcp"/><path class="mw42pob4d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bag-heart-line-duotone" {...props}></Icon>
