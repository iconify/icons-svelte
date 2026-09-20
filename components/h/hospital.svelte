<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x88jzdv6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x88jzdv6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:hospital" {...props}></Icon>
