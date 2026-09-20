<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2hvsab5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="u2hvsab5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:music-note-2-remix" {...props}></Icon>
