<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9--i9bid.css';
import '../../css/k/kp83vo4-e.css';
import '../../css/f/fcvnsw9zt.css';
import '../../css/i/i-otnfmzx.css';
import '../../css/a/ajh8fsxju.css';
import '../../css/n/n_fv7b7om.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w9--i9bid"/><path class="kp83vo4-e"/><path class="fcvnsw9zt"/><path class="i-otnfmzx"/><path class="ajh8fsxju"/><path class="n_fv7b7om"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ace-stream" {...props}></Icon>
