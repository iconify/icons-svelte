<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8pej69uk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m8pej69uk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-light" {...props}></Icon>
