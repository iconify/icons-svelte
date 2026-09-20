<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rllvkobji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rllvkobji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:link-2-off-sharp" {...props}></Icon>
