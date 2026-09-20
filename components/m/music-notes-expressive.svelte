<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4hjg1bud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u4hjg1bud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:music-notes-expressive" {...props}></Icon>
