<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qp1v2sdoj.css';
import '../../css/u/u2gs16bpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qp1v2sdoj"/><path class="u2gs16bpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextcloud-deck" {...props}></Icon>
