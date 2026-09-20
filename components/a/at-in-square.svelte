<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjh-x9b9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fjh-x9b9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:at-in-square" {...props}></Icon>
