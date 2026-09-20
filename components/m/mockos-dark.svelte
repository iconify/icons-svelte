<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3361obte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j3361obte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mockos-dark" {...props}></Icon>
