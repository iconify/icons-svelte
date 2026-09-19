<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdodvvbuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":560,"height":830};
const content = `<path class="vdodvvbuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:music" {...props}></Icon>
