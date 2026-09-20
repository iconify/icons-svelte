<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n20ttfvin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="n20ttfvin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:hospital" {...props}></Icon>
