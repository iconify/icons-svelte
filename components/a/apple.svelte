<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ry7vstmdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ry7vstmdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:apple" {...props}></Icon>
