<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-7lnjbeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="c-7lnjbeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:pause-circle-outline" {...props}></Icon>
