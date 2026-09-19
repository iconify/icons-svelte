<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7269db2g.css';
import '../../css/l/lmrf6zs5l.css';
import '../../css/b/bs0zlccnk.css';
import '../../css/q/q7i633bxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i7269db2g"/><path class="lmrf6zs5l"/><path class="bs0zlccnk"/><path class="q7i633bxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:relieved" {...props}></Icon>
