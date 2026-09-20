<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xstc6fbzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xstc6fbzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:accordion-menu" {...props}></Icon>
