<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/el39ovbzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="el39ovbzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:github-square" {...props}></Icon>
