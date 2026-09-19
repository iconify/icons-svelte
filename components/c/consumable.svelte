<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/i/i11jghbrq.css';
import '../../css/y/yngtobcdp.css';
import '../../css/w/wmhvecc2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i11jghbrq"/><path class="yngtobcdp"/><path class="wmhvecc2b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:consumable" {...props}></Icon>
