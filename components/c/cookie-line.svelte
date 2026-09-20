<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjtoopd_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pjtoopd_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:cookie-line" {...props}></Icon>
