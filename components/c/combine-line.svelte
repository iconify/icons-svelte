<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsqb-8i3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nsqb-8i3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:combine-line" {...props}></Icon>
