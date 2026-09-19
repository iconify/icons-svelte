<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tc-afobgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="tc-afobgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:caret-up" {...props}></Icon>
