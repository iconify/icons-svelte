<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vw_8thb5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vw_8thb5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:oven-mitts2" {...props}></Icon>
