<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqt44cdfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sqt44cdfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:mountains-sun" {...props}></Icon>
