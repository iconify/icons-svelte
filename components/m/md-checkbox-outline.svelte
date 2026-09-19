<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrhqy0n9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yrhqy0n9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-checkbox-outline" {...props}></Icon>
