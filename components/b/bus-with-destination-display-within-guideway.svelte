<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4cowz2em.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="c4cowz2em"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bus-with-destination-display-within-guideway" {...props}></Icon>
