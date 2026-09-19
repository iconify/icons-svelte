<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yg9mmgber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":384};
const content = `<path class="yg9mmgber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:plus-circle-o-duplicate" {...props}></Icon>
