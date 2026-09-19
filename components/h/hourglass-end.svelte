<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxwj6jb0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":24};
const content = `<path class="mxwj6jb0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:hourglass-end" {...props}></Icon>
