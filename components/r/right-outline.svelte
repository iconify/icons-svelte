<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3mve4_ly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="j3mve4_ly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:right-outline" {...props}></Icon>
