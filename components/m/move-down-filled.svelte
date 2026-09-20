<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3pdv4ixq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="s3pdv4ixq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:move-down-filled" {...props}></Icon>
