<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fq7w7gbnw.css';
import '../../css/d/dm_tx1bzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fq7w7gbnw"/><path class="dm_tx1bzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:logseq" {...props}></Icon>
