<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5ig9cc7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":49,"height":48};
const content = `<path class="c5ig9cc7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:bottom-bar-one" {...props}></Icon>
