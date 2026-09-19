<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8rq7tskk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c8rq7tskk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bolivia" {...props}></Icon>
