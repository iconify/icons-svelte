<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b225b0bzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b225b0bzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:noton-light" {...props}></Icon>
