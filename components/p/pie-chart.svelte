<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivro_3fld.css';
import '../../css/l/l6qh78cyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ivro_3fld"/><path class="l6qh78cyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:pie-chart" {...props}></Icon>
