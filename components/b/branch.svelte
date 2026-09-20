<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y98ul9c4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="y98ul9c4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:branch" {...props}></Icon>
