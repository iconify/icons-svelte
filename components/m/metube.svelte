<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1_zu51bb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j1_zu51bb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:metube" {...props}></Icon>
