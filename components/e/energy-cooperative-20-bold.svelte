<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/blnz3vcsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="blnz3vcsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:energy-cooperative-20-bold" {...props}></Icon>
