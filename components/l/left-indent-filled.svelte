<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hp4fgabrj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hp4fgabrj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:left-indent-filled" {...props}></Icon>
