<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h98hombod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h98hombod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:corner-upper-left" {...props}></Icon>
