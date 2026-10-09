<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6azyy2ro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x6azyy2ro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cone-20-bold" {...props}></Icon>
