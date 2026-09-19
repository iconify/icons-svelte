<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxfed015g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="bxfed015g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:arrow-right" {...props}></Icon>
