<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/stspny90z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="stspny90z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:folder" {...props}></Icon>
