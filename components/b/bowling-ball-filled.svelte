<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inb-mlxjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="inb-mlxjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bowling-ball-filled" {...props}></Icon>
