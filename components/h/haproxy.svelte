<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kievrdbdp.css';
import '../../css/n/nstbe3bzr.css';
import '../../css/u/uln8bqb4e.css';
import '../../css/z/z0qdkwbtn.css';
import '../../css/i/ip9tdh1yx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kievrdbdp"/><path class="nstbe3bzr"/><path class="uln8bqb4e"/><path class="z0qdkwbtn"/><path class="ip9tdh1yx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:haproxy" {...props}></Icon>
