<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_2lkqbxb.css';
import '../../css/m/map3bfdxa.css';
import '../../css/o/ofnyteubk.css';
import '../../css/x/x7sqjac5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="t_2lkqbxb"><path class="map3bfdxa"/><path class="ofnyteubk"/><path class="x7sqjac5b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:archive" {...props}></Icon>
