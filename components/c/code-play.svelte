<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aeh87fbxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aeh87fbxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:code-play" {...props}></Icon>
