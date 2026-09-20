<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/are8-xb3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="are8-xb3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:adobe" {...props}></Icon>
