<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqwvi89jg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jqwvi89jg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:box2-heart-fill" {...props}></Icon>
