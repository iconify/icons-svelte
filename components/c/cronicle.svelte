<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vk3q6nbal.css';
import '../../css/z/z1mt3ubli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vk3q6nbal"/><path class="z1mt3ubli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cronicle" {...props}></Icon>
