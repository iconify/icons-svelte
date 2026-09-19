<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/db-rwxb2n.css';
import '../../css/m/mcca7odma.css';
import '../../css/m/mc609bhih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="db-rwxb2n"/><path class="mcca7odma"/><path class="mc609bhih"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:dev-mode-phone" {...props}></Icon>
