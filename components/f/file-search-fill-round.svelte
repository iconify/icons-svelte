<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-_o76b0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c-_o76b0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:file-search-fill-round" {...props}></Icon>
