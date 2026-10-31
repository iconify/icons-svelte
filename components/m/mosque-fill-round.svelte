<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fsqarqbyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fsqarqbyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:mosque-fill-round" {...props}></Icon>
