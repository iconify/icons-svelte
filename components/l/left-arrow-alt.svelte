<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psx3-w2jj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="psx3-w2jj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:left-arrow-alt" {...props}></Icon>
