<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7qpb49an.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m7qpb49an"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-coffee-alt" {...props}></Icon>
