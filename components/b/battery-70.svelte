<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cq8je227t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cq8je227t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:battery-70" {...props}></Icon>
