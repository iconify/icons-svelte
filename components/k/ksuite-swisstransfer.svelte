<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx1ed53-h.css';
import '../../css/k/kmzi6e6ft.css';
import '../../css/j/josq1jb8s.css';
import '../../css/k/kmynck5lr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jx1ed53-h"/><path class="kmzi6e6ft"/><path class="josq1jb8s"/><path class="kmynck5lr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ksuite-swisstransfer" {...props}></Icon>
