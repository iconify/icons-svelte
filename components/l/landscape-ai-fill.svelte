<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/olkmp-6tv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="olkmp-6tv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:landscape-ai-fill" {...props}></Icon>
