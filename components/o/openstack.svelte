<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3t2cgbie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z3t2cgbie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:openstack" {...props}></Icon>
