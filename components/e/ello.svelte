<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/al2951bjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="al2951bjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:ello" {...props}></Icon>
