<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsar8eb2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dsar8eb2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:hight-lessen-outline" {...props}></Icon>
