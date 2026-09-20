<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plrm2twbs.css';
import '../../css/k/ku0zhsboo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="plrm2twbs"/><path class="ku0zhsboo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ipvanish" {...props}></Icon>
