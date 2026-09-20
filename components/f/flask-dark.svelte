<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcjwu4xpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rcjwu4xpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:flask-dark" {...props}></Icon>
