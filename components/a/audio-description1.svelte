<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gt-2qd5ac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gt-2qd5ac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:audio-description1" {...props}></Icon>
