<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mta_8o3fb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mta_8o3fb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:moment-fill" {...props}></Icon>
