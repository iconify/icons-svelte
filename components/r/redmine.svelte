<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqvr0v2ea.css';
import '../../css/u/uuehjku7c.css';
import '../../css/o/obrbe1bus.css';
import '../../css/w/w-m7llbyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qqvr0v2ea"/><path class="uuehjku7c"/><path class="obrbe1bus"/><path class="w-m7llbyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:redmine" {...props}></Icon>
