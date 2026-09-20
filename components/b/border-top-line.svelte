<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gn82-tbbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gn82-tbbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:border-top-line" {...props}></Icon>
