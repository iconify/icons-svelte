<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dfxyhsbxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dfxyhsbxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-shield-line" {...props}></Icon>
