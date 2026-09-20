<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lndl7fqqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lndl7fqqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:robot-face-happy-sharp" {...props}></Icon>
