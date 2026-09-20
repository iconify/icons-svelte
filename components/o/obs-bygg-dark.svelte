<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ms9p82buc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ms9p82buc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:obs-bygg-dark" {...props}></Icon>
