<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtc89hucc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1600};
const content = `<path class="gtc89hucc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:puzzle-piece" {...props}></Icon>
