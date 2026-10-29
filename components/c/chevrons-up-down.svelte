<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_sdfkb8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_sdfkb8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:chevrons-up-down" {...props}></Icon>
