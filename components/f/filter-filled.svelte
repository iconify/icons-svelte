<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhor8i0dv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vhor8i0dv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:filter-filled" {...props}></Icon>
