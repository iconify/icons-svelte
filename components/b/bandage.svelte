<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7vmzin9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="q7vmzin9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:bandage" {...props}></Icon>
