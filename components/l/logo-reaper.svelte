<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfqk1vksr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path clip-rule="evenodd" class="xfqk1vksr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:logo-reaper" {...props}></Icon>
