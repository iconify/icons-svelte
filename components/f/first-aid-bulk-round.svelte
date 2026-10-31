<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rc43jw5jh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rc43jw5jh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:first-aid-bulk-round" {...props}></Icon>
