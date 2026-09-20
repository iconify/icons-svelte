<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6pa3e19z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="h6pa3e19z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bridge-tied-arch" {...props}></Icon>
