<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jocuf1b7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jocuf1b7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:like" {...props}></Icon>
