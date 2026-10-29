<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/luuhupbtk.css';
import '../../css/g/gtinig8dd.css';
import '../../css/u/umj1g9evr.css';
import '../../css/d/d3u3pvbaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="luuhupbtk"/><path class="gtinig8dd"/><path class="umj1g9evr"/><path class="d3u3pvbaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:monitor" {...props}></Icon>
