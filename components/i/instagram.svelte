<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xif1tcbsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<defs><path id="SVGRu6oNd6B" class="xif1tcbsa"/></defs><use href="#SVGRu6oNd6B"/><use href="#SVGRu6oNd6B"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:instagram" {...props}></Icon>
