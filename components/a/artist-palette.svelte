<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/v6qwsy-jo.css';
import '../../css/p/pzipb6ixt.css';
import '../../css/g/gk74kzy9g.css';
import '../../css/o/odvyypb7e.css';
import '../../css/f/fod3o5b6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="v6qwsy-jo"/><path class="pzipb6ixt"/><path class="gk74kzy9g"/><path class="odvyypb7e"/><path class="fod3o5b6g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:artist-palette" {...props}></Icon>
