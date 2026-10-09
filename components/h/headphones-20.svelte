<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ad4zyr48f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ad4zyr48f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:headphones-20" {...props}></Icon>
