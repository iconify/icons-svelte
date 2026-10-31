<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdz1nabay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vdz1nabay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:container-gloss" {...props}></Icon>
