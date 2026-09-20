<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/todks38qn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="todks38qn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:moon-line" {...props}></Icon>
