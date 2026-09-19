<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/pjxpa7bda.css';
import '../../css/h/hb0tznocp.css';
import '../../css/i/inubnybbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="pjxpa7bda"/><path class="hb0tznocp"/><path class="inubnybbc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:logo-webhook" {...props}></Icon>
