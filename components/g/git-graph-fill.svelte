<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ph-0pdbbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ph-0pdbbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:git-graph-fill" {...props}></Icon>
