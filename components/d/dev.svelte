<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2px2_-ky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="q2px2_-ky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:dev" {...props}></Icon>
