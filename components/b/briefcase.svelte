<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ar3vc0bla.css';
import '../../css/u/u7oh6pfab.css';
import '../../css/m/mg0joeral.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/o/otio0yb-k.css';
import '../../css/i/ihhy2s8-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="ar3vc0bla"/><path class="u7oh6pfab"/><path class="mg0joeral"/><g class="jn8qy4bru"><path class="otio0yb-k"/><path class="ihhy2s8-o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:briefcase" {...props}></Icon>
