<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aevmiibvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aevmiibvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-volume-mute" {...props}></Icon>
