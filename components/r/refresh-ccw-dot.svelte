<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ae0hrvqsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ae0hrvqsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:refresh-ccw-dot" {...props}></Icon>
