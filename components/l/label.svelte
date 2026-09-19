<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hv62pmbfb.css';
import '../../css/t/ta90ekbqr.css';
import '../../css/v/vhqenwbef.css';
import '../../css/u/unrbvebfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="hv62pmbfb"/><path class="ta90ekbqr"/><path class="vhqenwbef"/><path class="unrbvebfg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:label" {...props}></Icon>
