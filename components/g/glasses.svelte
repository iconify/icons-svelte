<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xl5suacty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="xl5suacty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:glasses" {...props}></Icon>
