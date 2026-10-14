<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrfln6yfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jrfln6yfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:coffer-light" {...props}></Icon>
