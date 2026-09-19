<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a47_abbvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="a47_abbvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:group-work" {...props}></Icon>
