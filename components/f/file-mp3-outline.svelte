<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oesttb3lj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="oesttb3lj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:file-mp3-outline" {...props}></Icon>
