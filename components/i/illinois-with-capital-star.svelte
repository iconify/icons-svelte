<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbf2a2b4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jbf2a2b4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:illinois-with-capital-star" {...props}></Icon>
