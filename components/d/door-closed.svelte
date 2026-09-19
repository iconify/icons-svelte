<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksvyc4bov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1216,"height":1632};
const content = `<path class="ksvyc4bov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:door-closed" {...props}></Icon>
