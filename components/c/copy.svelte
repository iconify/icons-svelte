<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/snll855pf.css';
import '../../css/e/e80hdkb-p.css';
import '../../css/u/upimrikml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="snll855pf"/><path class="e80hdkb-p"/><path class="upimrikml"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:copy" {...props}></Icon>
