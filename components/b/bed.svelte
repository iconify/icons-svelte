<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plt19qbyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="plt19qbyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bed" {...props}></Icon>
