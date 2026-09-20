<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q27ejebhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q27ejebhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:rocket-2-line" {...props}></Icon>
