<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2erelhux.css';
import '../../css/r/rs7efhi1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m2erelhux"/><path class="rs7efhi1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:playlist-20" {...props}></Icon>
