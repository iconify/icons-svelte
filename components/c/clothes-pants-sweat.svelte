<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/o/olbdy62vw.css';
import '../../css/e/er6jam89u.css';
import '../../css/n/n6zdtvbbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="olbdy62vw"/><path class="er6jam89u"/><path class="n6zdtvbbl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:clothes-pants-sweat" {...props}></Icon>
