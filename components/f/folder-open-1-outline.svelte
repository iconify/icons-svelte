<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9yt1cc9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="m9yt1cc9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:folder-open-1-outline" {...props}></Icon>
