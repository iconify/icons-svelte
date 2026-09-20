<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmwnbcc0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dmwnbcc0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:dinner-fill" {...props}></Icon>
