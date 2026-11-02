<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r387op9rr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r387op9rr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:partly-cloud-daytime-line" {...props}></Icon>
