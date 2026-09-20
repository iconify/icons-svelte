<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/op39z1b0t.css';
import '../../css/f/fjiyggelq.css';
import '../../css/x/xfcsm6b8b.css';
import '../../css/b/bbj_fcggl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="op39z1b0t"/><path class="fjiyggelq"/><path class="xfcsm6b8b"/><path class="bbj_fcggl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:paper-bin-line-duotone" {...props}></Icon>
