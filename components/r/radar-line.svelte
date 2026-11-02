<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7tv91l-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x7tv91l-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:radar-line" {...props}></Icon>
