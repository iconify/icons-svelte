<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mumuo9s8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mumuo9s8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:folder-search-gloss" {...props}></Icon>
