<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ys7dy7tqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ys7dy7tqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:key-plus" {...props}></Icon>
