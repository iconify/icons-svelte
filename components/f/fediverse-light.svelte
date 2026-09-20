<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6fjo6bor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r6fjo6bor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fediverse-light" {...props}></Icon>
