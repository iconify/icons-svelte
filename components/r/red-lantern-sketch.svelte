<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/f6346fozd.css';
import '../../css/a/atzm8bc8c.css';
import '../../css/e/embnm_8cc.css';
import '../../css/a/aumnm37ge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="f6346fozd"/><path class="atzm8bc8c wm-k"/><path class="embnm_8cc wm-k"/><path class="aumnm37ge wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:red-lantern-sketch" {...props}></Icon>
