<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcuu3-d9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="rcuu3-d9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:emergency-call-remix" {...props}></Icon>
