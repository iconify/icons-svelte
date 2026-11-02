<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwzk0jram.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rwzk0jram"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cigarette-fill" {...props}></Icon>
