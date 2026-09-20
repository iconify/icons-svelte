<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hy4bwaboj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hy4bwaboj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:audio-tape-fill" {...props}></Icon>
