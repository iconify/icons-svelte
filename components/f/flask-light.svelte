<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0r1s99fd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="u0r1s99fd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:flask-light" {...props}></Icon>
