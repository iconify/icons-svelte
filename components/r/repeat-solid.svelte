<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/in4ubz10s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="in4ubz10s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:repeat-solid" {...props}></Icon>
