<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2nzhhb7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="m2nzhhb7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pentagram-in-circle-outline" {...props}></Icon>
