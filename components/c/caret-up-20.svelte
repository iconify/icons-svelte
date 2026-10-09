<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k91r7qbds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="k91r7qbds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:caret-up-20" {...props}></Icon>
