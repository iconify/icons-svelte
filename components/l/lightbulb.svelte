<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvxdfup1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":352,"height":512};
const content = `<path class="qvxdfup1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:lightbulb" {...props}></Icon>
