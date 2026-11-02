<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fm4n3ybtj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fm4n3ybtj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:electric-cooker-fill" {...props}></Icon>
