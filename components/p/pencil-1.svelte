<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mcz2a8bsd.css';
import '../../css/q/qagdjebam.css';
import '../../css/c/c6eoz-bnz.css';
import '../../css/v/v89bqvxpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="mcz2a8bsd"/><path clip-rule="evenodd" class="qagdjebam"/><path clip-rule="evenodd" class="c6eoz-bnz"/><path class="v89bqvxpp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:pencil-1" {...props}></Icon>
