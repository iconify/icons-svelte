<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgv26-uju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jgv26-uju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:arrow-circle-down" {...props}></Icon>
