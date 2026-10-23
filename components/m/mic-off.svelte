<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rv0bvo2fd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rv0bvo2fd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:mic-off" {...props}></Icon>
