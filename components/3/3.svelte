<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6tplefgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="r6tplefgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:3" {...props}></Icon>
