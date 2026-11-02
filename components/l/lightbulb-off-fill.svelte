<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9_obhquk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g9_obhquk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:lightbulb-off-fill" {...props}></Icon>
