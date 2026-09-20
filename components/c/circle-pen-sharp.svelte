<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0g7uzbot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j0g7uzbot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-pen-sharp" {...props}></Icon>
