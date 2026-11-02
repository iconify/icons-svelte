<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzine-gxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tzine-gxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:heavy-rain-fill" {...props}></Icon>
