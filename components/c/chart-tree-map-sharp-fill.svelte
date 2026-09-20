<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmynbzbcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zmynbzbcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chart-tree-map-sharp-fill" {...props}></Icon>
