<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tv8-ysf4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tv8-ysf4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:caret-down" {...props}></Icon>
