<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9qqxib9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z9qqxib9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ko-fi-dark" {...props}></Icon>
