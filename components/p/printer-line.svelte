<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r44tmacvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r44tmacvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:printer-line" {...props}></Icon>
