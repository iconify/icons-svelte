<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g86mqw3do.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g86mqw3do"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cactus-2-line" {...props}></Icon>
