<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ro1qxybqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ro1qxybqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:opnsense-dark" {...props}></Icon>
