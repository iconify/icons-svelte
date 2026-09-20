<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffz5o973p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ffz5o973p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pi-source-light" {...props}></Icon>
