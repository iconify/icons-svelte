<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gl4uohhkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gl4uohhkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:magnifying-glass-arrow-right" {...props}></Icon>
