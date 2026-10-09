<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rldubof9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rldubof9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:minus-20-bold" {...props}></Icon>
