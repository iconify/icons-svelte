<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q88cta02b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q88cta02b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flip-horizontal-line" {...props}></Icon>
