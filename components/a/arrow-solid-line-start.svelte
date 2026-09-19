<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kvhy3dyow.css';
import '../../css/y/ywz-ofbgu.css';
import '../../css/c/c0gb28b5d.css';
import '../../css/g/g0lu956-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="kvhy3dyow"/><path class="ywz-ofbgu"/><path class="c0gb28b5d"/><path class="g0lu956-m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:arrow-solid-line-start" {...props}></Icon>
