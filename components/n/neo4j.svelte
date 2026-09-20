<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o67-rbbrh.css';
import '../../css/k/kv7scgbdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o67-rbbrh"/><path class="kv7scgbdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:neo4j" {...props}></Icon>
