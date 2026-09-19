<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dy6_9_bea.css';
import '../../css/p/pmwtv-rax.css';
import '../../css/x/xai6gubor.css';
import '../../css/y/yosw-cc2e.css';
import '../../css/d/dbgippb-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="dy6_9_bea"/><path class="pmwtv-rax"/><path class="xai6gubor"/><path class="yosw-cc2e"/><path class="dbgippb-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:ghost" {...props}></Icon>
