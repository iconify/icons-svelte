<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/d/db8x5vb9v.css';
import '../../css/f/fq0ry90aj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g class="y9tr6bcfx"><path class="db8x5vb9v"/><circle class="fq0ry90aj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-calendar-setting-calendar-cog-date-day-gear-load-loading-month-setting-work" {...props}></Icon>
