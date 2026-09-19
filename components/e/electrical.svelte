<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g52e4xb1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="g52e4xb1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:electrical" {...props}></Icon>
