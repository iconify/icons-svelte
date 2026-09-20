<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwa1keyih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bwa1keyih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:paragraph" {...props}></Icon>
