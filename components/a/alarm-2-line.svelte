<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccfpk9bpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ccfpk9bpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:alarm-2-line" {...props}></Icon>
