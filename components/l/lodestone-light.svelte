<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymi50ubsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ymi50ubsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lodestone-light" {...props}></Icon>
