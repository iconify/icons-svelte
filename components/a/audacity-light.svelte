<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjjdp8c7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pjjdp8c7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:audacity-light" {...props}></Icon>
