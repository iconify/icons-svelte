<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvtk8fuky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qvtk8fuky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:facebook" {...props}></Icon>
