<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/idcg027iu.css';
import '../../css/k/kh9rsjb-p.css';
import '../../css/v/v7xgjhbst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="idcg027iu"/><path class="kh9rsjb-p"/><path class="v7xgjhbst"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:file-validation" {...props}></Icon>
