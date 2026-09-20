<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yp25m2b2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yp25m2b2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-letter-f-filled" {...props}></Icon>
