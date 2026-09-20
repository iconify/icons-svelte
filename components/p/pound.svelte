<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvjkalbit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="vvjkalbit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:pound" {...props}></Icon>
