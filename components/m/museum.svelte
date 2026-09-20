<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyte08niz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hyte08niz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:museum" {...props}></Icon>
