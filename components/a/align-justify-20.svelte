<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_9sazb0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x_9sazb0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:align-justify-20" {...props}></Icon>
