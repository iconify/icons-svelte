<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/an5t5je8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="an5t5je8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:exit-door-fill" {...props}></Icon>
