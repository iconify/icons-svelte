<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isovy3byi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="isovy3byi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:budibase-dark" {...props}></Icon>
