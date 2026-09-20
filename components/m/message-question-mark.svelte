<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr52f_b5y.css';
import '../../css/u/uifzf81kd.css';
import '../../css/l/lvunf81kr.css';
import '../../css/m/mupqf7bjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><path class="uifzf81kd"/><path class="lvunf81kr"/><path class="mupqf7bjj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:message-question-mark" {...props}></Icon>
