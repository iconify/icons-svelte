<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_h52ebxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z_h52ebxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:avatar-teen-gloss" {...props}></Icon>
