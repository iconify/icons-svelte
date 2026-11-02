<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzbz7fr0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fzbz7fr0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chart-column-big-line" {...props}></Icon>
