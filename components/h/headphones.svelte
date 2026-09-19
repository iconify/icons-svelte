<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpn0tfite.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1408};
const content = `<path class="dpn0tfite"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:headphones" {...props}></Icon>
