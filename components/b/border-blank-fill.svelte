<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6t5y4_fb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j6t5y4_fb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:border-blank-fill" {...props}></Icon>
