<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozic-irzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ozic-irzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bridge-2-line" {...props}></Icon>
