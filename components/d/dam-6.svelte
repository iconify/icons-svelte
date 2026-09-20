<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/x2fs-hbnn.css';
import '../../css/x/xfrvrlbcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="x2fs-hbnn"/><path class="xfrvrlbcw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:dam-6" {...props}></Icon>
