<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhddsfbhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="jhddsfbhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:haproxy-wordmark" {...props}></Icon>
