<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zkrl-8bgb.css';
import '../../css/g/g8ydabckk.css';
import '../../css/m/m35k5sbte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zkrl-8bgb"/><path class="g8ydabckk"/><path class="m35k5sbte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:postiz" {...props}></Icon>
