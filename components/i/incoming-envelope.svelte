<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2s1gywra.css';
import '../../css/l/lzoghccnd.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/w/wp9nfebcy.css';
import '../../css/k/kq1305ues.css';
import '../../css/a/a732xmrfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<rect class="g2s1gywra"/><path class="lzoghccnd"/><g class="jn8qy4bru"><path class="wp9nfebcy"/><path class="kq1305ues"/><path class="a732xmrfu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:incoming-envelope" {...props}></Icon>
