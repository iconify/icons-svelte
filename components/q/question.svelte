<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_53iob0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y_53iob0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:question" {...props}></Icon>
