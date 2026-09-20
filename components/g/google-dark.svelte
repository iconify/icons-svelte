<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c24govbmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c24govbmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-dark" {...props}></Icon>
