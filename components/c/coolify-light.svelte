<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sonzv-b6i.css';
import '../../css/y/y41okqbrh.css';
import '../../css/e/e1nqa7bmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sonzv-b6i"/><path class="y41okqbrh"/><path class="e1nqa7bmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:coolify-light" {...props}></Icon>
