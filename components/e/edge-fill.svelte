<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcv0d51xo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pcv0d51xo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:edge-fill" {...props}></Icon>
