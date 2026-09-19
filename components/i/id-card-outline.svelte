<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpam7qbjh.css';
import '../../css/h/h0x9monpf.css';
import '../../css/w/wbip20b7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<rect class="gpam7qbjh"/><path class="h0x9monpf"/><path class="wbip20b7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:id-card-outline" {...props}></Icon>
