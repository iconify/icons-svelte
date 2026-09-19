<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/em5dqch8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="em5dqch8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:camera" {...props}></Icon>
