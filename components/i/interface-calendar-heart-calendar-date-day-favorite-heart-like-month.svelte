<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/g/gq5mk-mss.css';
import '../../css/u/uf4zisbfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g class="y9tr6bcfx"><path class="gq5mk-mss"/><path class="uf4zisbfd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-calendar-heart-calendar-date-day-favorite-heart-like-month" {...props}></Icon>
