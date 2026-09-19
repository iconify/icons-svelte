<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvv9p2b3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="mvv9p2b3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:circlethree" {...props}></Icon>
