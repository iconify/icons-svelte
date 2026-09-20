<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc_a9dblh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bc_a9dblh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fli-so-dark" {...props}></Icon>
