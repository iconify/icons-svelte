<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nl9mpu3fh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nl9mpu3fh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:css-stroke-20" {...props}></Icon>
