<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvc-bxpqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yvc-bxpqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:alibaba-dark" {...props}></Icon>
