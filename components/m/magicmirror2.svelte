<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1ydcvb-h.css';
import '../../css/n/n3w0hhuyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o1ydcvb-h"/><path class="n3w0hhuyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:magicmirror2" {...props}></Icon>
