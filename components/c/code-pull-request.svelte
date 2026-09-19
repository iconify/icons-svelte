<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sahn3db4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="sahn3db4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:code-pull-request" {...props}></Icon>
