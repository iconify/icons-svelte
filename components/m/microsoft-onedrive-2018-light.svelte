<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kuxcp-t-s.css';
import '../../css/q/qhvaocbxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kuxcp-t-s"/><path class="qhvaocbxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-onedrive-2018-light" {...props}></Icon>
