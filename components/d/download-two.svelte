<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzgxucbjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hzgxucbjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:download-two" {...props}></Icon>
