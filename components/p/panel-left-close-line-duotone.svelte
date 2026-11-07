<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/j/j-3yojbro.css';
import '../../css/v/vbwan82rd.css';
import '../../css/v/v3-yjpbpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="j-3yojbro"/><path class="vbwan82rd"/><path class="v3-yjpbpv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panel-left-close-line-duotone" {...props}></Icon>
