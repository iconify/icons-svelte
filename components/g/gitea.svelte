<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikxd3jb2y.css';
import '../../css/b/b3ex35ova.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ikxd3jb2y"/><path class="b3ex35ova"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:gitea" {...props}></Icon>
