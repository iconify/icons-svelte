<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-0dsebfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e-0dsebfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:heading-6-fill" {...props}></Icon>
