<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ff6aicbic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ff6aicbic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nomad-travel" {...props}></Icon>
