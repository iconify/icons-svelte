<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxx6f10mk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rxx6f10mk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:bluetooth" {...props}></Icon>
