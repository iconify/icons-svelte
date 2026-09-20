<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edz9rxbaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="edz9rxbaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:railway-track-crossing-striped-line" {...props}></Icon>
