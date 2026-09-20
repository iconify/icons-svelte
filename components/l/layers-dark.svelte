<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iebp_9cqm.css';
import '../../css/i/ilr4rab5a.css';
import '../../css/a/a4bu9h0na.css';
import '../../css/p/pskf2nb6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":33};
const content = `<g class="iebp_9cqm"><path class="ilr4rab5a"/><path class="a4bu9h0na"/><path class="pskf2nb6x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:layers-dark" {...props}></Icon>
