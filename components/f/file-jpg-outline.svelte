<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyx366rwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hyx366rwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:file-jpg-outline" {...props}></Icon>
