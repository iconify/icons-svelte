<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9cn8b7_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="n9cn8b7_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:italic" {...props}></Icon>
