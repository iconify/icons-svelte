<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_9j9ppgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y_9j9ppgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:obs-bygg-light" {...props}></Icon>
