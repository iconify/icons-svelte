<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_s7w5bve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b_s7w5bve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:folder-search-corner-fill-round" {...props}></Icon>
