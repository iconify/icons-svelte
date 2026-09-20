<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qa63bdbwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="qa63bdbwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:play-store" {...props}></Icon>
