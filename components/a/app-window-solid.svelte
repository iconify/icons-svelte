<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dv5ay4byl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dv5ay4byl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:app-window-solid" {...props}></Icon>
