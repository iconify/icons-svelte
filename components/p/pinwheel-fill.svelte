<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvnvor-hs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mvnvor-hs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pinwheel-fill" {...props}></Icon>
