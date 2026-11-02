<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enrlyzw_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="enrlyzw_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:image-off-fill" {...props}></Icon>
