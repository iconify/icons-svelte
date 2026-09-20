<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yh_n6absf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yh_n6absf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:flood-light" {...props}></Icon>
