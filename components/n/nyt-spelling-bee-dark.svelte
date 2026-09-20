<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eg9qh-kkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eg9qh-kkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nyt-spelling-bee-dark" {...props}></Icon>
