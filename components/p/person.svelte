<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r099o0npj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r099o0npj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:person" {...props}></Icon>
