<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sw_yoi_9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sw_yoi_9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:audio-lines" {...props}></Icon>
