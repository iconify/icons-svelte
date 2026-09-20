<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_rmp6ypz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="u_rmp6ypz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pixel-three-inch-floppy-disk" {...props}></Icon>
