<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8tqqyu7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d8tqqyu7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:drink-line" {...props}></Icon>
