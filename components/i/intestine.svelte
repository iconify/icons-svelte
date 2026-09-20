<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7e7cjszb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="m7e7cjszb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:intestine" {...props}></Icon>
