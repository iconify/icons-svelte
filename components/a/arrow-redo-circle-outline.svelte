<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adblgzbva.css';
import '../../css/y/ybwzvccuq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="adblgzbva"/><path class="ybwzvccuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:arrow-redo-circle-outline" {...props}></Icon>
