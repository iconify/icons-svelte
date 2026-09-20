<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3s3fb6sn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="g3s3fb6sn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:north-dakota" {...props}></Icon>
