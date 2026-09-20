<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6huf2bix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s6huf2bix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:matter" {...props}></Icon>
