<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ss-z11x0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ss-z11x0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:frame" {...props}></Icon>
