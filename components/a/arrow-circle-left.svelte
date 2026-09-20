<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yx8sjhbvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yx8sjhbvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:arrow-circle-left" {...props}></Icon>
