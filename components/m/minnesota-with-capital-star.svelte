<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n43-wcaxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="n43-wcaxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:minnesota-with-capital-star" {...props}></Icon>
