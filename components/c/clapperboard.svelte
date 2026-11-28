<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clngo6w0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="clngo6w0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:clapperboard" {...props}></Icon>
