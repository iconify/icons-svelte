<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agc9_jb8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="agc9_jb8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:frigate" {...props}></Icon>
