<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rb3zijiqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="rb3zijiqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:phone-flat" {...props}></Icon>
