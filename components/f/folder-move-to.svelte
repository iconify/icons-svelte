<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/li9q4lu4g.css';
import '../../css/r/rvbsrrkcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="li9q4lu4g"/><path class="rvbsrrkcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:folder-move-to" {...props}></Icon>
