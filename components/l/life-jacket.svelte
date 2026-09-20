<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mkzkov_zo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mkzkov_zo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:life-jacket" {...props}></Icon>
