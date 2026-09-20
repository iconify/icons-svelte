<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfpvy8bur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="bfpvy8bur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:hourglass3" {...props}></Icon>
