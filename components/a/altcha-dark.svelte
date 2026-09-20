<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9y-1ji3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m9y-1ji3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:altcha-dark" {...props}></Icon>
