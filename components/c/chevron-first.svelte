<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwc28duwl.css';
import '../../css/p/p0vvxskvk.css';
import '../../css/r/r51vm3woy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pwc28duwl wm-k"/><path class="p0vvxskvk wm-k"/><path class="r51vm3woy wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:chevron-first" {...props}></Icon>
