<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/b/b32gsdbth.css';
import '../../css/i/iwqeqib9j.css';
import '../../css/n/neojpkb-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="b32gsdbth"/><path class="iwqeqib9j"/><path class="neojpkb-z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:play-cycle" {...props}></Icon>
