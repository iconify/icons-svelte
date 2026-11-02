<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3mcfnwtu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r3mcfnwtu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:close-medium-line" {...props}></Icon>
