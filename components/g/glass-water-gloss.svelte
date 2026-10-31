<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/blvwms0oy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="blvwms0oy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:glass-water-gloss" {...props}></Icon>
