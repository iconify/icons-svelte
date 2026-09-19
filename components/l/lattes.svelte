<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nw9gkzbll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="nw9gkzbll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:lattes" {...props}></Icon>
