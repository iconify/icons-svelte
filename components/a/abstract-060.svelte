<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2stk6dwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j2stk6dwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-060" {...props}></Icon>
