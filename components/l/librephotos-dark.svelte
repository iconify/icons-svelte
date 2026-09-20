<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8mup3byn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b8mup3byn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:librephotos-dark" {...props}></Icon>
