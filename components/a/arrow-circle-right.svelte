<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3w_afb3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w3w_afb3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:arrow-circle-right" {...props}></Icon>
