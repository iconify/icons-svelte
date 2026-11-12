<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hm1o5ccoz.css';
import '../../css/o/obkkoglrp.css';
import '../../css/p/p34lxkxwh.css';
import '../../css/i/i-gsmlpun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hm1o5ccoz"/><path class="obkkoglrp"/><path class="p34lxkxwh"/><path class="i-gsmlpun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ksuite-kdrive" {...props}></Icon>
