<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6ucx0b-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="l6ucx0b-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:ellipsis" {...props}></Icon>
