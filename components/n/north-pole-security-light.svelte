<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5cvzbc-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r5cvzbc-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:north-pole-security-light" {...props}></Icon>
