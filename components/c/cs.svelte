<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_4k5e69h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="j_4k5e69h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:cs" {...props}></Icon>
