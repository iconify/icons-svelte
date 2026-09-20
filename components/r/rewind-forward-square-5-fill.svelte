<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrnmp8poh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wrnmp8poh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rewind-forward-square-5-fill" {...props}></Icon>
