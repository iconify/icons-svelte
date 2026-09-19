<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fw7l1ccln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fw7l1ccln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-slack-old" {...props}></Icon>
