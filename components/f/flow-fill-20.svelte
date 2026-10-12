<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8uofudft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i8uofudft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:flow-fill-20" {...props}></Icon>
