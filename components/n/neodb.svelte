<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xik-vs_jl.css';
import '../../css/o/owdhvpbwp.css';
import '../../css/k/kt2xtwbum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xik-vs_jl"/><path class="owdhvpbwp"/><path class="kt2xtwbum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:neodb" {...props}></Icon>
