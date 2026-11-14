<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qy1acevxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qy1acevxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:image-flip-horizontal" {...props}></Icon>
