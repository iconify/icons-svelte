<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fb0yldbeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1408};
const content = `<path class="fb0yldbeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:pencil-square-o" {...props}></Icon>
