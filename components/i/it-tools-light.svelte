<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ab7nlyb2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ab7nlyb2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:it-tools-light" {...props}></Icon>
