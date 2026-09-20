<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ut-rukwjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ut-rukwjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:guitar-line" {...props}></Icon>
