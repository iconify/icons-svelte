<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhdbmwbnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1022};
const content = `<path class="fhdbmwbnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:certificate" {...props}></Icon>
