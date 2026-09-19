<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ss-s9gi8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ss-s9gi8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:empty-set" {...props}></Icon>
