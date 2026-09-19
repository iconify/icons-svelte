<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m496c9reb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m496c9reb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bong-filled" {...props}></Icon>
