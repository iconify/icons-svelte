<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwlqrq5ch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rwlqrq5ch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:mail" {...props}></Icon>
