<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ml5gl5ako.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1536};
const content = `<path class="ml5gl5ako"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:comment-o" {...props}></Icon>
