<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/z/zn-9lpbfa.css';
import '../../css/x/xtlfw0b-a.css';
import '../../css/b/b-sovabka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="zn-9lpbfa"/><path class="wm-k xtlfw0b-a"/><path class="b-sovabka wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:cloud-alert-sketch" {...props}></Icon>
