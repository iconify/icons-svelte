<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sucw5zbdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sucw5zbdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:codepen-fill" {...props}></Icon>
