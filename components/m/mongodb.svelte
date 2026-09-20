<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-08wh0_j.css';
import '../../css/v/vnuucwq6l.css';
import '../../css/s/s7cf2jbnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s-08wh0_j"/><path class="vnuucwq6l"/><path class="s7cf2jbnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mongodb" {...props}></Icon>
