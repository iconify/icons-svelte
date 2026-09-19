<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svn71h5bl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":448};
const content = `<path class="svn71h5bl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:friendster" {...props}></Icon>
