<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6n8tjbud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j6n8tjbud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:dashboard-2-line" {...props}></Icon>
