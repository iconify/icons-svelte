<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w050vtbit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w050vtbit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:robot-line" {...props}></Icon>
