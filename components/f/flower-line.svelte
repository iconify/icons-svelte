<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmx0jjb4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kmx0jjb4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flower-line" {...props}></Icon>
