<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ka_x1487y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ka_x1487y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:home-modern" {...props}></Icon>
