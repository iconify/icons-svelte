<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ae7x5gbcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ae7x5gbcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:arrow-diagonal-bottom-left" {...props}></Icon>
