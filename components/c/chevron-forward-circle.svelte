<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jczl-lz0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jczl-lz0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:chevron-forward-circle" {...props}></Icon>
