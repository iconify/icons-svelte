<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u90snccqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="u90snccqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:mqtt" {...props}></Icon>
