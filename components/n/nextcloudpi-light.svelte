<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymi_3kb1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ymi_3kb1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextcloudpi-light" {...props}></Icon>
