<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pleo8ac3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pleo8ac3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:lamp-solid" {...props}></Icon>
