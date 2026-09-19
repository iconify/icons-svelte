<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwmc9j4zj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mwmc9j4zj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:help-circle" {...props}></Icon>
