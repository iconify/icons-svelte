<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdmi7-6-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="jdmi7-6-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:arrow-right-to-city" {...props}></Icon>
