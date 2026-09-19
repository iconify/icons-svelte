<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2-a7hcnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h2-a7hcnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:gear-fill-16" {...props}></Icon>
