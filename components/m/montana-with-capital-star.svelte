<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fh2ov0byk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fh2ov0byk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:montana-with-capital-star" {...props}></Icon>
