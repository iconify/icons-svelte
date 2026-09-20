<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w97ft0xpq.css';
import '../../css/h/hn37esb2k.css';
import '../../css/p/pb8rmtbxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w97ft0xpq"/><path class="hn37esb2k"/><path class="pb8rmtbxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ksuite-manager-dark" {...props}></Icon>
