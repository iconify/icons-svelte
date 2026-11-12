<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxnmy9bde.css';
import '../../css/m/mjttu00lo.css';
import '../../css/g/gmago3blo.css';
import '../../css/x/x-mqmdlpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bxnmy9bde"/><path class="mjttu00lo"/><path class="gmago3blo"/><path class="x-mqmdlpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:excalidash-dark" {...props}></Icon>
