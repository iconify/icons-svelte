<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usoukvb3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":408,"height":392};
const content = `<path class="usoukvb3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:local-dining" {...props}></Icon>
