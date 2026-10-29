<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/z/zlkpuxbnl.css';
import '../../css/b/b1djw6bjn.css';
import '../../css/n/na0nesucf.css';
import '../../css/o/o3oli_b6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="zlkpuxbnl"/><path class="b1djw6bjn wm-a"/><path class="na0nesucf wm-k"/><path class="o3oli_b6e wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:alert-triangle-sketch" {...props}></Icon>
