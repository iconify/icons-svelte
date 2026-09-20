<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1q5labdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v1q5labdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:file-cdr-outline" {...props}></Icon>
