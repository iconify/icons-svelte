<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnrr2voyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rnrr2voyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cloud-alt-filled" {...props}></Icon>
