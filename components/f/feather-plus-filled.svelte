<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgkic680g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vgkic680g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:feather-plus-filled" {...props}></Icon>
