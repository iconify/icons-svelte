<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jh-wsvyto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jh-wsvyto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:arrow-undo" {...props}></Icon>
