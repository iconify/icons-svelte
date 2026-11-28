<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yawk1-b1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yawk1-b1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:layers" {...props}></Icon>
