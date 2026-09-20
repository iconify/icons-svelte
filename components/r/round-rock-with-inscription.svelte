<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6weuyb7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="t6weuyb7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:round-rock-with-inscription" {...props}></Icon>
