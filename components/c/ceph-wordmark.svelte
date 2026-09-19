<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxt2zmbsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="xxt2zmbsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:ceph-wordmark" {...props}></Icon>
