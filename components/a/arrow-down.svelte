<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urvau44ne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="urvau44ne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:arrow-down" {...props}></Icon>
