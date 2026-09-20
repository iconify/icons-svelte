<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bf3jhqdyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="bf3jhqdyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:add-circle-small" {...props}></Icon>
