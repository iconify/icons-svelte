<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rod79qbyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rod79qbyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:matter-dark" {...props}></Icon>
