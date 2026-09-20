<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7ic7cc0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g7ic7cc0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:location-arrow-circle" {...props}></Icon>
