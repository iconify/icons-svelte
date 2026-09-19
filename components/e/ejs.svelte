<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xo57adrhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xo57adrhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:ejs" {...props}></Icon>
