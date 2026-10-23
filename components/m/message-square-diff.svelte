<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4ii9b3nm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x4ii9b3nm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:message-square-diff" {...props}></Icon>
