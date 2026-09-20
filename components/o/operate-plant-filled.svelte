<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bb9rh5boj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="bb9rh5boj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:operate-plant-filled" {...props}></Icon>
