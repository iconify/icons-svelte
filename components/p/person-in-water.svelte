<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x67rembyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="x67rembyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-in-water" {...props}></Icon>
