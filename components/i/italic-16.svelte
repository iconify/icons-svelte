<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqn8-vbkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tqn8-vbkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:italic-16" {...props}></Icon>
