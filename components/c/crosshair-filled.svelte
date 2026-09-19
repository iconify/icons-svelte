<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6a9ptc7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m6a9ptc7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:crosshair-filled" {...props}></Icon>
