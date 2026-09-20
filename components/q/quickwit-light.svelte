<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmyb9zu8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tmyb9zu8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:quickwit-light" {...props}></Icon>
