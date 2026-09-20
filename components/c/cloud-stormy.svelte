<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9725xb3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l9725xb3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:cloud-stormy" {...props}></Icon>
