<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbqt5xw6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mbqt5xw6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:hawaii" {...props}></Icon>
