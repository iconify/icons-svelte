<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usqribf4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="usqribf4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layers-minus-line" {...props}></Icon>
