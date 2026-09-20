<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uc9lqz1-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="uc9lqz1-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:chess-king-remix" {...props}></Icon>
