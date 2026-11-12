<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqr0zm-hq.css';
import '../../css/n/n2x5xwbjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bqr0zm-hq"/><path class="n2x5xwbjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dosvault-light" {...props}></Icon>
