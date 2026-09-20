<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3jv8dbwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="s3jv8dbwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:oval-broadleaved-tree-beside-oval-broadleaved-tree-on-ground" {...props}></Icon>
