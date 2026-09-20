<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p35k1cbwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p35k1cbwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:building-off" {...props}></Icon>
