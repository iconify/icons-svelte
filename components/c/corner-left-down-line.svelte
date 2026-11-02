<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivq7ni1-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ivq7ni1-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:corner-left-down-line" {...props}></Icon>
