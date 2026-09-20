<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1bwmk63r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q1bwmk63r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:crunchyroll-dark" {...props}></Icon>
