<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkd9qz5fj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="pkd9qz5fj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:cog" {...props}></Icon>
