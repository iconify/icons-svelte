<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sl50bob_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sl50bob_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:anticlockwise-alt-line" {...props}></Icon>
