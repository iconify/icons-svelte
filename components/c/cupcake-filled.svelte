<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1jo01bna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y1jo01bna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cupcake-filled" {...props}></Icon>
