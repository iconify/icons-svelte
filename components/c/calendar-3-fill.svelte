<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxg9oubsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nxg9oubsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:calendar-3-fill" {...props}></Icon>
