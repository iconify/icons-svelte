<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l08dbnbxs.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/j/je0c3ho1m.css';
import '../../css/c/ca9qziunz.css';
import '../../css/k/kjbro8bqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="l08dbnbxs"/><g class="jn8qy4bru"><path class="je0c3ho1m"/><path class="ca9qziunz"/><path class="kjbro8bqb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:index-pointing-at-the-viewer-medium-dark-skin-tone" {...props}></Icon>
