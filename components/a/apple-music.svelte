<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/di7sjtb7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="di7sjtb7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:apple-music" {...props}></Icon>
