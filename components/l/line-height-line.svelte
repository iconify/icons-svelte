<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iy8ogs3oi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iy8ogs3oi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:line-height-line" {...props}></Icon>
