<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yp3qq1znw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yp3qq1znw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:power-tower-portal" {...props}></Icon>
