<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g83s5tbcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":657,"height":770};
const content = `<path class="g83s5tbcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:android" {...props}></Icon>
