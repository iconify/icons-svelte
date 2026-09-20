<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbosynb8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vbosynb8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:perses" {...props}></Icon>
