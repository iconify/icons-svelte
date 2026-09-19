<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjw1ds2yi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="wjw1ds2yi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:file-zipper" {...props}></Icon>
