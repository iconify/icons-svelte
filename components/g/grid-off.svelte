<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1oftvbsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e1oftvbsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:grid-off" {...props}></Icon>
