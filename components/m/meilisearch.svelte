<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8x9wd4ds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r8x9wd4ds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:meilisearch" {...props}></Icon>
