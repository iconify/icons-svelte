<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcm3z1pyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pcm3z1pyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:onskeskyen-light" {...props}></Icon>
