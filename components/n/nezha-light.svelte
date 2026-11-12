<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b30i0rbgm.css';
import '../../css/e/e_k2sgbhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b30i0rbgm"/><path class="e_k2sgbhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nezha-light" {...props}></Icon>
