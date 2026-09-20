<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjx051b5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yjx051b5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:part-of-circle" {...props}></Icon>
