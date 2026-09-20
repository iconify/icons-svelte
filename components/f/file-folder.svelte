<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwzl1fkot.css';
import '../../css/m/mye8w2bqk.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/n/nzou8ob_j.css';
import '../../css/d/dq091-iyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="cwzl1fkot"/><path class="mye8w2bqk"/><g class="jn8qy4bru"><path class="nzou8ob_j"/><path class="dq091-iyu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:file-folder" {...props}></Icon>
