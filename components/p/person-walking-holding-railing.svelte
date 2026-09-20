<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gopuiz2dq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gopuiz2dq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-walking-holding-railing" {...props}></Icon>
