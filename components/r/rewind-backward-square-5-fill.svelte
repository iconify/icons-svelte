<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgj-9x8dp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cgj-9x8dp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rewind-backward-square-5-fill" {...props}></Icon>
