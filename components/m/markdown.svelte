<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qto-1actj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="qto-1actj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:markdown" {...props}></Icon>
