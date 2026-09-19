<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yz966bb_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yz966bb_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:pencil" {...props}></Icon>
