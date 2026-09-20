<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fz0almbde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fz0almbde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:color" {...props}></Icon>
