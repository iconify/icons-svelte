<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lx46h8f9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lx46h8f9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:cluster" {...props}></Icon>
