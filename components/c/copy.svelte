<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yv1-oda_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yv1-oda_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:copy" {...props}></Icon>
