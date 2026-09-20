<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t91-bib1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="t91-bib1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:cutlery" {...props}></Icon>
