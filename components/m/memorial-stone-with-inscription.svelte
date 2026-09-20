<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xw9aoy2ge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xw9aoy2ge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:memorial-stone-with-inscription" {...props}></Icon>
