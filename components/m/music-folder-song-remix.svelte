<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzh9wkb2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="dzh9wkb2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:music-folder-song-remix" {...props}></Icon>
