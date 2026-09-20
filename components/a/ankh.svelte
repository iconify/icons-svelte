<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmky_1t8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gmky_1t8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:ankh" {...props}></Icon>
