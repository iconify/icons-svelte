<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qthw8xbzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qthw8xbzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:fishing-area-2" {...props}></Icon>
