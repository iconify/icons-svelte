<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqrgs8bmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gqrgs8bmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:neo" {...props}></Icon>
