<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e54cwys7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e54cwys7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:internet-archive-dark" {...props}></Icon>
