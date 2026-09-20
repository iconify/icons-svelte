<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fv9z5ty7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fv9z5ty7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-walking" {...props}></Icon>
