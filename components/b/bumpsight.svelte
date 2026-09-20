<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ro6wwmbtu.css';
import '../../css/s/sxbjysb0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<ellipse class="ro6wwmbtu"/><path class="sxbjysb0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bumpsight" {...props}></Icon>
