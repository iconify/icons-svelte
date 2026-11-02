<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgh__w-ay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qgh__w-ay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:live-photo-line" {...props}></Icon>
