<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcm0_su8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pcm0_su8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:react" {...props}></Icon>
