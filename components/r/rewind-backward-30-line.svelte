<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7i9bg0qp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j7i9bg0qp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rewind-backward-30-line" {...props}></Icon>
