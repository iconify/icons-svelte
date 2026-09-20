<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5-oqd5ef.css';
import '../../css/n/nhikcvf6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="p5-oqd5ef"/><path class="nhikcvf6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:rippling" {...props}></Icon>
