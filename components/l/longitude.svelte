<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k7grn9x-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k7grn9x-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:longitude" {...props}></Icon>
