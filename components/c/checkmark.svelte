<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ucujz0b4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ucujz0b4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:checkmark" {...props}></Icon>
