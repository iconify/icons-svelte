<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ko-4xac8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ko-4xac8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:life-in-the-balance" {...props}></Icon>
