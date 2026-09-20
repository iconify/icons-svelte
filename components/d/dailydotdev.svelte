<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x512z4xmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x512z4xmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:dailydotdev" {...props}></Icon>
