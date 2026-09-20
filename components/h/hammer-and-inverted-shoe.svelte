<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d03a88bzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="d03a88bzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:hammer-and-inverted-shoe" {...props}></Icon>
