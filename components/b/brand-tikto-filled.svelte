<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yk8flv62h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yk8flv62h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-tikto-filled" {...props}></Icon>
