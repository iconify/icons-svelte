<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pygc13kpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pygc13kpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:disc-album-fill" {...props}></Icon>
