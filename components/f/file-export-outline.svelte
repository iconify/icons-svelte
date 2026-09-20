<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cafx1-b8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cafx1-b8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:file-export-outline" {...props}></Icon>
