<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8xlj6v0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i8xlj6v0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:comment" {...props}></Icon>
