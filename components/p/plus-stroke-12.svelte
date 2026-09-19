<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/erhjj-75b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="erhjj-75b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:plus-stroke-12" {...props}></Icon>
