<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/le_tmjbos.css';
import '../../css/r/rx80esbgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="le_tmjbos"/><path class="rx80esbgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fandango" {...props}></Icon>
