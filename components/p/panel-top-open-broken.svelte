<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/tp0liacle.css';
import '../../css/w/wip28lbxr.css';
import '../../css/q/quujejbhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="tp0liacle"/><path class="wip28lbxr"/><path class="quujejbhk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panel-top-open-broken" {...props}></Icon>
