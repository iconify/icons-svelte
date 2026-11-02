<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6kdn1rcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q6kdn1rcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flower-3-fill" {...props}></Icon>
