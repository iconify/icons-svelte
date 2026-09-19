<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7rcn_r6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g7rcn_r6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cctv-filled" {...props}></Icon>
