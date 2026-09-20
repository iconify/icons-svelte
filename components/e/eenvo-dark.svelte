<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2j-smfbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c2j-smfbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:eenvo-dark" {...props}></Icon>
