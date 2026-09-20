<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j86dveb1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j86dveb1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:microsoft-bing" {...props}></Icon>
