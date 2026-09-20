<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rx3ofnbit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rx3ofnbit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:megafone" {...props}></Icon>
