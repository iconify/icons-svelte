<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6yhym3bm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j6yhym3bm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arrow-curve-left-down" {...props}></Icon>
