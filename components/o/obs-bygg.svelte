<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jywu-rbdx.css';
import '../../css/x/x228u46nd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jywu-rbdx"/><path class="x228u46nd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:obs-bygg" {...props}></Icon>
