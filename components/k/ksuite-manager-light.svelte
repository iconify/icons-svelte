<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmg31mbbr.css';
import '../../css/y/yq4ktg_2p.css';
import '../../css/q/qxwq8bcbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wmg31mbbr"/><path class="yq4ktg_2p"/><path class="qxwq8bcbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ksuite-manager-light" {...props}></Icon>
