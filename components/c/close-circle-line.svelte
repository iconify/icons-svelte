<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cu1yncb7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cu1yncb7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:close-circle-line" {...props}></Icon>
