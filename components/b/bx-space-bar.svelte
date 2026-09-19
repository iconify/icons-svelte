<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7q6n-bve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q7q6n-bve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-space-bar" {...props}></Icon>
