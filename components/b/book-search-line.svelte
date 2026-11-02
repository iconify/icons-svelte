<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/caph1n78r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="caph1n78r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:book-search-line" {...props}></Icon>
