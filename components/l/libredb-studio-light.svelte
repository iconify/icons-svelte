<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qw46dbp2r.css';
import '../../css/y/y8e-4bcjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qw46dbp2r"/><path class="y8e-4bcjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:libredb-studio-light" {...props}></Icon>
