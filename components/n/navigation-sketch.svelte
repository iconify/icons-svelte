<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/vrf_umb-v.css';
import '../../css/j/jpoivdq2g.css';
import '../../css/d/dz-1iivjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="vrf_umb-v"/><path class="jpoivdq2g"/><path class="dz-1iivjd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:navigation-sketch" {...props}></Icon>
