<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpd9i4kyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jpd9i4kyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:bed-single-outline" {...props}></Icon>
