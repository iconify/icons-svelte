<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/alente67r.css';
import '../../css/k/kby-w4n6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="alente67r"/><path class="kby-w4n6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:open-source-initiative" {...props}></Icon>
