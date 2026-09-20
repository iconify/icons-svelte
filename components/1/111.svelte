<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxtkoeb2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="oxtkoeb2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:111" {...props}></Icon>
