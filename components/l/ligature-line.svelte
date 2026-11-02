<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7t-_0t7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f7t-_0t7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ligature-line" {...props}></Icon>
