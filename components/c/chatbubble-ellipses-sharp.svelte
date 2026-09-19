<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jztg1xb4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jztg1xb4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:chatbubble-ellipses-sharp" {...props}></Icon>
