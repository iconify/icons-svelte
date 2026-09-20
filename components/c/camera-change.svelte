<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/js23lzbnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="js23lzbnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:camera-change" {...props}></Icon>
