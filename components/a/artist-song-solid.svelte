<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6skg3cyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="p6skg3cyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:artist-song-solid" {...props}></Icon>
