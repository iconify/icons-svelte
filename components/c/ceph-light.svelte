<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ed6msyqpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ed6msyqpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ceph-light" {...props}></Icon>
