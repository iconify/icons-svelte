<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-qoz2f0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r-qoz2f0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:brush" {...props}></Icon>
