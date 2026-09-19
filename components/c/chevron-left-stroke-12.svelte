<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5xoo-b6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="h5xoo-b6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:chevron-left-stroke-12" {...props}></Icon>
