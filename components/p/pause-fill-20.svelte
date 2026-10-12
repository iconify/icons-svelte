<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urcr4j1xg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="urcr4j1xg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:pause-fill-20" {...props}></Icon>
