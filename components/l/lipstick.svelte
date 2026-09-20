<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmgati1sa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pmgati1sa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:lipstick" {...props}></Icon>
