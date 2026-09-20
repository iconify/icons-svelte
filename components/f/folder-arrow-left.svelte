<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bn7t-fbvk.css';
import '../../css/l/ll5_hob1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bn7t-fbvk"/><path clip-rule="evenodd" class="ll5_hob1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:folder-arrow-left" {...props}></Icon>
