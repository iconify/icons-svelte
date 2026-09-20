<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjg4do0um.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vjg4do0um"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:arrow-thick-down" {...props}></Icon>
