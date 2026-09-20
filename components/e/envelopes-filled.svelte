<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/vh7avqmdc.css';
import '../../css/o/ouv_s_bld.css';
import '../../css/e/ekkzpbcrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vh7avqmdc"/><path class="ouv_s_bld"/><path class="ekkzpbcrm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:envelopes-filled" {...props}></Icon>
