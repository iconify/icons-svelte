<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/baki4loqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="baki4loqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:listenarr" {...props}></Icon>
