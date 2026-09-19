<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfs75p2ck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="pfs75p2ck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:common-data-service-c-d-s" {...props}></Icon>
