<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0aa-ibik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r0aa-ibik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:delete-2-line" {...props}></Icon>
