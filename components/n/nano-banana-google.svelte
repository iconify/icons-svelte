<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjm9s1b5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cjm9s1b5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:nano-banana-google" {...props}></Icon>
