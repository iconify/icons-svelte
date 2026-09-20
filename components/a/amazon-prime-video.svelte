<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5-2j9bts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u5-2j9bts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:amazon-prime-video" {...props}></Icon>
