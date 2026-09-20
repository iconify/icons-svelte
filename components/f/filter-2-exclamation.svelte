<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1edqiffe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n1edqiffe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:filter-2-exclamation" {...props}></Icon>
