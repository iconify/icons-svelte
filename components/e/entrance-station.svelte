<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8fzmcbjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="q8fzmcbjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:entrance-station" {...props}></Icon>
