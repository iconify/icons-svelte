<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9xvu1gdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x9xvu1gdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rotate-y-line" {...props}></Icon>
