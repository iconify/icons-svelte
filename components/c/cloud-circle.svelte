<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r50l1jf5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r50l1jf5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:cloud-circle" {...props}></Icon>
