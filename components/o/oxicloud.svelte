<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwr2epb-t.css';
import '../../css/s/swf58-3sr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="vwr2epb-t"/><path class="swf58-3sr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:oxicloud" {...props}></Icon>
