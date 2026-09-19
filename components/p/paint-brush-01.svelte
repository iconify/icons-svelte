<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fr3rnzvyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fr3rnzvyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:paint-brush-01" {...props}></Icon>
