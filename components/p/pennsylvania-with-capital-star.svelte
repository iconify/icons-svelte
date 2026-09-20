<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhztmo4mr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yhztmo4mr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pennsylvania-with-capital-star" {...props}></Icon>
