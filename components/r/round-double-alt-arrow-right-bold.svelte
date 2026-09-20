<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5yg6700j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h5yg6700j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:round-double-alt-arrow-right-bold" {...props}></Icon>
