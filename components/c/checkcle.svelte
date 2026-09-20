<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mz9fp19zf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mz9fp19zf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:checkcle" {...props}></Icon>
