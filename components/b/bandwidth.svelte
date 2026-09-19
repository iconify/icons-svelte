<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ec6prebfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ec6prebfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:bandwidth" {...props}></Icon>
