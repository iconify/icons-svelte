<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndo8zjz9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ndo8zjz9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:import" {...props}></Icon>
