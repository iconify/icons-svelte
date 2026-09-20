<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l09wnubxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l09wnubxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:folder-search" {...props}></Icon>
