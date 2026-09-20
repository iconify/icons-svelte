<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rk7w6qbmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rk7w6qbmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:flag-pin" {...props}></Icon>
