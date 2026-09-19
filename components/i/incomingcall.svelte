<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvysm6ifx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1025};
const content = `<path class="lvysm6ifx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:incomingcall" {...props}></Icon>
