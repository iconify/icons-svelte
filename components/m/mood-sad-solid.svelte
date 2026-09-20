<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6y8m1bqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m6y8m1bqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:mood-sad-solid" {...props}></Icon>
