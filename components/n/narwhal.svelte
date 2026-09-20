<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffww1eb2m.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/x/x2ylpqyvn.css';
import '../../css/b/bn-8nobfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="ffww1eb2m"/><g class="jn8qy4bru"><path class="x2ylpqyvn"/><path class="bn-8nobfm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:narwhal" {...props}></Icon>
