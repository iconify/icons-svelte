<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5e21pb0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1025};
const content = `<path class="p5e21pb0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:barchartdesc" {...props}></Icon>
