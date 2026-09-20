<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/js-e04bid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="js-e04bid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:layers-intersect-outline" {...props}></Icon>
